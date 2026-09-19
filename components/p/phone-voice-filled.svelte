<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yimxbdbkz.css';
import '../../css/i/i-nbabcvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yimxbdbkz"/><path class="i-nbabcvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:phone-voice-filled" {...props}></Icon>
