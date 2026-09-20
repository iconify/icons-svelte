<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwzxh9b8m.css';
import '../../css/w/wfizkjosn.css';
import '../../css/p/pz2e0kkio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwzxh9b8m"/><path class="wfizkjosn"/><path class="pz2e0kkio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:download" {...props}></Icon>
