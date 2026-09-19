<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yimxbdbkz.css';
import '../../css/c/cfhd2dbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yimxbdbkz"/><path class="cfhd2dbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:phone-voice" {...props}></Icon>
