<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbopo_bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jbopo_bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flat-paw-print" {...props}></Icon>
