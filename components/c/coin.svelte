<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbsst6bep.css';
import '../../css/h/h7gro1emj.css';
import '../../css/r/r3sjlmblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xbsst6bep"/><path class="h7gro1emj"/><path class="r3sjlmblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:coin" {...props}></Icon>
