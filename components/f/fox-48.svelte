<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8o7jbnvk.css';
import '../../css/x/x0f0yioou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s8o7jbnvk"/><path class="x0f0yioou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fox-48" {...props}></Icon>
