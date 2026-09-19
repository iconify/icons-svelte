<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec_0u4bpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ec_0u4bpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:animal-hide" {...props}></Icon>
