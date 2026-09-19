<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky_qdhb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ky_qdhb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cargo-ship" {...props}></Icon>
