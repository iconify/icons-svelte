<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y02gaibli.css';
import '../../css/w/wgcfbo68c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="y02gaibli"/><path class="wgcfbo68c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:antarctica" {...props}></Icon>
