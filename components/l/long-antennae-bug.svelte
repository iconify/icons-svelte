<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdxjo73ia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wdxjo73ia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:long-antennae-bug" {...props}></Icon>
