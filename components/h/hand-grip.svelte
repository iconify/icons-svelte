<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-3m_utop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d-3m_utop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hand-grip" {...props}></Icon>
