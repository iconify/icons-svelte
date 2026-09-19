<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqmgz0doi.css';
import '../../css/l/ld018kbkh.css';
import '../../css/f/f60e8jbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jqmgz0doi"/><path class="ld018kbkh"/><path class="f60e8jbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:money" {...props}></Icon>
