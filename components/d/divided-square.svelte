<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfpcg0b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xfpcg0b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:divided-square" {...props}></Icon>
