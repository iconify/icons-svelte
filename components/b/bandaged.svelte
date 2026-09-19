<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_eewhbcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o_eewhbcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bandaged" {...props}></Icon>
