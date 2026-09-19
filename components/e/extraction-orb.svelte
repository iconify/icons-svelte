<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3m_y-zfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c3m_y-zfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:extraction-orb" {...props}></Icon>
