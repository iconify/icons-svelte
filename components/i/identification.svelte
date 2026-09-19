<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdhl94coo.css';
import '../../css/l/lzvsylpnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tdhl94coo"/><path class="lzvsylpnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:identification" {...props}></Icon>
