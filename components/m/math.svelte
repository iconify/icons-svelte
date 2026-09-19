<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyg2p5f5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyg2p5f5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:math" {...props}></Icon>
