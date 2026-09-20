<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeck0ilxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xeck0ilxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:double-quote-serif-right" {...props}></Icon>
