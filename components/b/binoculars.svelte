<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfs_podua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hfs_podua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:binoculars" {...props}></Icon>
