<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw_jc_5dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="iw_jc_5dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-solid-circle-bold" {...props}></Icon>
