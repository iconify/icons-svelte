<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv8mvflwb.css';
import '../../css/j/jefef3bul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uv8mvflwb"/><path class="jefef3bul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-prismatic-20-bold" {...props}></Icon>
