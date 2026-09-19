<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq1k364qb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vq1k364qb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mineral-heart" {...props}></Icon>
