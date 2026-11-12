<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy901f9ms.css';
import '../../css/n/n-5kzabfr.css';
import '../../css/d/d0_q4g1fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="vy901f9ms"/><path class="n-5kzabfr"/><path class="d0_q4g1fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beets-flask-dark" {...props}></Icon>
