<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scd922beo.css';
import '../../css/r/rsyv-4sjc.css';
import '../../css/a/aqo8lubpi.css';
import '../../css/x/x7qr8mbdd.css';
import '../../css/g/gp2g9ybnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="scd922beo"/><path class="rsyv-4sjc"/><circle class="aqo8lubpi"/><circle class="x7qr8mbdd"/><circle class="gp2g9ybnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:list-circle-outline" {...props}></Icon>
