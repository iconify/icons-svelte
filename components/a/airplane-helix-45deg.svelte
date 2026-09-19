<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufie9ebgy.css';
import '../../css/l/llp5f-z2n.css';
import '../../css/w/w-mce9o4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ufie9ebgy"><path class="llp5f-z2n"/><path clip-rule="evenodd" class="w-mce9o4q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:airplane-helix-45deg" {...props}></Icon>
