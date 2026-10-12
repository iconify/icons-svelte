<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzbdracbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uzbdracbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bolt-off-48" {...props}></Icon>
