<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_0rlkxdi.css';
import '../../css/l/l1uhs48mi.css';
import '../../css/y/ygoprobme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a_0rlkxdi"/><circle class="l1uhs48mi"/><circle class="ygoprobme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:global-threat-map-dark" {...props}></Icon>
