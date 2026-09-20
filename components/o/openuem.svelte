<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqzar5xlv.css';
import '../../css/e/eo4l80r5n.css';
import '../../css/n/nd0_hkbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="zqzar5xlv"/><path class="eo4l80r5n"/><path class="nd0_hkbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openuem" {...props}></Icon>
