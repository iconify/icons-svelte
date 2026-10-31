<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kormnebaz.css';
import '../../css/p/pixfiacte.css';
import '../../css/o/oda795b_c.css';
import '../../css/g/gd5oyhbtz.css';
import '../../css/f/fptu256yt.css';
import '../../css/h/hds49-bqk.css';
import '../../css/t/t8_cs4vzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kormnebaz"/><path class="pixfiacte"/><path class="oda795b_c"/><path class="gd5oyhbtz"/><path class="fptu256yt"/><path class="hds49-bqk"/><path class="t8_cs4vzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:cream" {...props}></Icon>
