<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxbe2vbtu.css';
import '../../css/z/ziq40nb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fxbe2vbtu"/><path class="ziq40nb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:emptynote" {...props}></Icon>
