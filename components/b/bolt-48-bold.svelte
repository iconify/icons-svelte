<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgy96wbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dgy96wbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bolt-48-bold" {...props}></Icon>
