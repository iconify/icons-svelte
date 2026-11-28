<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt1z6xbjk.css';
import '../../css/p/plng_wb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary wt1z6xbjk"/><path class="plng_wb5t primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-off-page-duo" {...props}></Icon>
