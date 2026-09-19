<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdl_kk0km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="mdl_kk0km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-line-end" {...props}></Icon>
