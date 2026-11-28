<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6l_spbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="u6l_spbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:image-plus" {...props}></Icon>
