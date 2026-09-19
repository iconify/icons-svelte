<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6cinp7vj.css';
import '../../css/l/ly_uttqof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l6cinp7vj"/><path class="ly_uttqof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-process-mining" {...props}></Icon>
