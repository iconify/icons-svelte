<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jey-zbbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jey-zbbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:close-solid" {...props}></Icon>
