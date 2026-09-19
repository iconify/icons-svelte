<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc71ixbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tc71ixbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-047" {...props}></Icon>
