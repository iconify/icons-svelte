<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx7_61w8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dx7_61w8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bugle-call" {...props}></Icon>
