<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elb82nbbj.css';
import '../../css/a/aewymtpsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="elb82nbbj"/><path class="aewymtpsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:power-sleep-symbol" {...props}></Icon>
