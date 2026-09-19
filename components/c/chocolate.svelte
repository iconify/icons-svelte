<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gnu5dik5b.css';
import '../../css/q/q4rumib0w.css';
import '../../css/v/vp5nx6b1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gnu5dik5b"/><path class="q4rumib0w"/><path class="vp5nx6b1u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chocolate" {...props}></Icon>
