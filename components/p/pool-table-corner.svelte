<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdoipbzxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zdoipbzxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pool-table-corner" {...props}></Icon>
