<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_lqdbbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z_lqdbbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lightning-tear" {...props}></Icon>
