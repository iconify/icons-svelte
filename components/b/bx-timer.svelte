<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0hb-y1ml.css';
import '../../css/d/dn9k9z1wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0hb-y1ml"/><path class="dn9k9z1wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-timer" {...props}></Icon>
