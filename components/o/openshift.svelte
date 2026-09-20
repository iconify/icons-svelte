<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-4_v9njk.css';
import '../../css/d/dw2j3ebeq.css';
import '../../css/s/st1ujobif.css';
import '../../css/r/r25huvknw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m-4_v9njk"/><path class="dw2j3ebeq"/><path class="st1ujobif"/><path class="r25huvknw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openshift" {...props}></Icon>
