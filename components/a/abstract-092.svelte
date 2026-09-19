<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_ou2mbsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_ou2mbsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-092" {...props}></Icon>
