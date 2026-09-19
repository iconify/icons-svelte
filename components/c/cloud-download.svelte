<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/w/wuu1i6jkg.css';
import '../../css/j/ji85o5n5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wuu1i6jkg"/><path class="ji85o5n5b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cloud-download" {...props}></Icon>
