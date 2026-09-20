<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik8j_0m_s.css';
import '../../css/l/lm0uu894d.css';
import '../../css/i/iltdgbc8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ik8j_0m_s"/><path class="lm0uu894d"/><path class="iltdgbc8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-anomaly-detection" {...props}></Icon>
