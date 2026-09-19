<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wc4-75bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wc4-75bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-022" {...props}></Icon>
