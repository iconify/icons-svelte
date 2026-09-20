<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnrmsfh-l.css';
import '../../css/h/hdnx13uec.css';
import '../../css/r/ruvlv2d2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gnrmsfh-l"/><path class="hdnx13uec"/><path class="ruvlv2d2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cross-seed" {...props}></Icon>
