<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc9z0ibda.css';
import '../../css/m/m_t120kfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uc9z0ibda"/><path class="m_t120kfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:jersey-48" {...props}></Icon>
