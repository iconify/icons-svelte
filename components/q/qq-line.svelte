<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u265_o_gg.css';
import '../../css/f/fwtgwcf6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u265_o_gg"/><path class="fwtgwcf6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:qq-line" {...props}></Icon>
