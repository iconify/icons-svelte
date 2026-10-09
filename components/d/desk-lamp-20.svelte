<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh-egpbpk.css';
import '../../css/p/pzb63_vzh.css';
import '../../css/n/n4ap65bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sh-egpbpk"/><path class="pzb63_vzh"/><path class="n4ap65bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:desk-lamp-20" {...props}></Icon>
