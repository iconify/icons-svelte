<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_yur1g1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m_yur1g1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cliparr" {...props}></Icon>
