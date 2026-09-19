<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo_8_sedt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo_8_sedt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:microscope-solid" {...props}></Icon>
