<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyglj2bnx.css';
import '../../css/d/dkassfuyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qyglj2bnx"/><path class="dkassfuyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-body-outline" {...props}></Icon>
