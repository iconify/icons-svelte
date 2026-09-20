<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrj-3pr-l.css';
import '../../css/a/alzpy97nw.css';
import '../../css/w/w0xawxcgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrj-3pr-l"/><path class="alzpy97nw"/><path class="w0xawxcgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:charging-flash-wifi-bold" {...props}></Icon>
