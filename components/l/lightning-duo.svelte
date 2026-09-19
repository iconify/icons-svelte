<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mcfvnubzm.css';
import '../../css/q/q0wxspbkv.css';
import '../../css/g/gaqtzmgzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="mcfvnubzm"/><path class="q0wxspbkv"/><path class="gaqtzmgzk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:lightning-duo" {...props}></Icon>
