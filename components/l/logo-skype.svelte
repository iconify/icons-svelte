<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5aom4pxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f5aom4pxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-skype" {...props}></Icon>
