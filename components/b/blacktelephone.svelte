<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inrii0mwj.css';
import '../../css/y/yukot35yn.css';
import '../../css/c/ctunfubbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="inrii0mwj"/><path class="yukot35yn"/><path class="ctunfubbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blacktelephone" {...props}></Icon>
