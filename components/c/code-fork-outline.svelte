<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjwj2pbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjwj2pbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:code-fork-outline" {...props}></Icon>
