<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziltb3b7d.css';
import '../../css/w/wh9r_4xsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ziltb3b7d"/><path class="wh9r_4xsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hmx" {...props}></Icon>
