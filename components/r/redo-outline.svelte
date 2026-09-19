<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyp3-vbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyp3-vbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:redo-outline" {...props}></Icon>
