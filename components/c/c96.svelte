<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxsozccmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vxsozccmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:c96" {...props}></Icon>
