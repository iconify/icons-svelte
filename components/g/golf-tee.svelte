<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw1-d_wqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nw1-d_wqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:golf-tee" {...props}></Icon>
