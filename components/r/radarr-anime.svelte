<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db2xgugay.css';
import '../../css/g/gi2xlrbzn.css';
import '../../css/u/u4j5hjbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="db2xgugay"/><path class="gi2xlrbzn"/><path class="u4j5hjbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:radarr-anime" {...props}></Icon>
