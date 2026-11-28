<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2wbkcbbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="k2wbkcbbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:passport-light" {...props}></Icon>
