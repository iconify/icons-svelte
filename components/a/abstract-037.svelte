<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuor6xgkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yuor6xgkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-037" {...props}></Icon>
