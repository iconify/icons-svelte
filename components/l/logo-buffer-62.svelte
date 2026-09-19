<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_1es1p0u.css';
import '../../css/i/iny3_db3v.css';
import '../../css/u/uvnpe-bqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y_1es1p0u"/><path class="iny3_db3v"/><path class="uvnpe-bqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-buffer-62" {...props}></Icon>
