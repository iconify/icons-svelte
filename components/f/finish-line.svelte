<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybdgcfh4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ybdgcfh4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:finish-line" {...props}></Icon>
