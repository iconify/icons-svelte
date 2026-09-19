<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc3jcqkcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bc3jcqkcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:layered-armor" {...props}></Icon>
