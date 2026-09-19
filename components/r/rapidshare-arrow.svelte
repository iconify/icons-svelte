<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_m_e5evi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e_m_e5evi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rapidshare-arrow" {...props}></Icon>
