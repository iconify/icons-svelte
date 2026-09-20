<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_q4zpj6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m_q4zpj6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cups-light" {...props}></Icon>
