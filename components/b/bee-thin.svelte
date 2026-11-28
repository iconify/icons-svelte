<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izn1bdsiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="izn1bdsiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bee-thin" {...props}></Icon>
