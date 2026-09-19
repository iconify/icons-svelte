<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csa0z4bwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="csa0z4bwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:picnic-table" {...props}></Icon>
