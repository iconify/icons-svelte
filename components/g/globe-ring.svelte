<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8d1w2iyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w8d1w2iyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:globe-ring" {...props}></Icon>
