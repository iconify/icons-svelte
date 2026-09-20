<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drphl9x-c.css';
import '../../css/q/q6evf3_3i.css';
import '../../css/g/g-vas9vud.css';
import '../../css/h/ha2s1vbvi.css';
import '../../css/a/ay8131wny.css';
import '../../css/g/ggi7iyb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="drphl9x-c"/><path class="q6evf3_3i"/><path class="g-vas9vud"/><path class="ha2s1vbvi"/><circle class="ay8131wny"/><path class="ggi7iyb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:blue-book" {...props}></Icon>
