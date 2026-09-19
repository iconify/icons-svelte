<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmy-rlt6c.css';
import '../../css/l/l144cxb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xmy-rlt6c"/><path class="l144cxb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-game-controller-b" {...props}></Icon>
