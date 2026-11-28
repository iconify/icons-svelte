<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdfvp4bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdfvp4bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:headphones-check" {...props}></Icon>
