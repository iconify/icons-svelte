<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_ey53f3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m_ey53f3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:energy-arrow" {...props}></Icon>
