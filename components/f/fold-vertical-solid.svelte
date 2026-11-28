<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w08qh4blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w08qh4blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:fold-vertical-solid" {...props}></Icon>
