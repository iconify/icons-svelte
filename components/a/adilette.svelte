<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmi6-ac-z.css';
import '../../css/r/riq5x4hsf.css';
import '../../css/m/mnfqy7zah.css';
import '../../css/z/z6kq0x6kj.css';
import '../../css/v/vs3wopbcv.css';
import '../../css/q/qubs_6bnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="hmi6-ac-z"/><path class="riq5x4hsf"/><path class="mnfqy7zah"/><path class="z6kq0x6kj"/><path class="vs3wopbcv"/><path class="qubs_6bnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:adilette" {...props}></Icon>
