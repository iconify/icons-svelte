<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sne2qlnhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sne2qlnhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:post-stamp" {...props}></Icon>
