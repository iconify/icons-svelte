<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0e4m_qgc.css';
import '../../css/x/xbfokwbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m0e4m_qgc"/><path class="xbfokwbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:acquiremock" {...props}></Icon>
