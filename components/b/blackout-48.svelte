<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gaiyacb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gaiyacb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:blackout-48" {...props}></Icon>
