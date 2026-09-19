<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f75bf_bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f75bf_bdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:quick-slash" {...props}></Icon>
