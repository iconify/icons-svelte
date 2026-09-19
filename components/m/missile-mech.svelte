<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe0m_79-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fe0m_79-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:missile-mech" {...props}></Icon>
