<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt_dcj1zc.css';
import '../../css/v/vd8fnkbgj.css';
import '../../css/i/i424kzrcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jt_dcj1zc"/><path class="vd8fnkbgj"/><path class="i424kzrcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gatus" {...props}></Icon>
