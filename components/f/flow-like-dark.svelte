<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1m_q4b0x.css';
import '../../css/w/wfa-59b9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v1m_q4b0x"/><path class="wfa-59b9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flow-like-dark" {...props}></Icon>
