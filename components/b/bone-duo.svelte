<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkza45u4w.css';
import '../../css/i/iik494jlc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkza45u4w secondary"/><path class="iik494jlc primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bone-duo" {...props}></Icon>
