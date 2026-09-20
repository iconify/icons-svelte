<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf8md-ebl.css';
import '../../css/n/nzlse_b6a.css';
import '../../css/d/d0_q4g1fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="xf8md-ebl"/><path class="nzlse_b6a"/><path class="d0_q4g1fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beets-flask-dark" {...props}></Icon>
