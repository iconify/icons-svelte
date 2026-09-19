<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc_22bcyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zc_22bcyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crypt-entrance" {...props}></Icon>
