<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt968xbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="wt968xbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:codex" {...props}></Icon>
