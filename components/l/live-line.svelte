<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbbc40btb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbbc40btb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:live-line" {...props}></Icon>
