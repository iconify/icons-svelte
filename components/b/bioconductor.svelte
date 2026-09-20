<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-ulpdbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-ulpdbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:bioconductor" {...props}></Icon>
