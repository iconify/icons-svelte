<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4s43wbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4s43wbec primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:microscope-duotone" {...props}></Icon>
