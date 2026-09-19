<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbg970wgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbg970wgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:google" {...props}></Icon>
