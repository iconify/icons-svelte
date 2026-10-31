<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqwhos75l.css';
import '../../css/a/alqkqccyy.css';
import '../../css/i/i2wpqi2td.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="rqwhos75l"/><path class="alqkqccyy"/><path class="i2wpqi2td"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:oman" {...props}></Icon>
