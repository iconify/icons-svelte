<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/tnigo-8vb.css';
import '../../css/b/b7rjdgn0s.css';
import '../../css/y/y0889gbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="tnigo-8vb"/><path class="b7rjdgn0s"/><path class="y0889gbgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:node-add" {...props}></Icon>
