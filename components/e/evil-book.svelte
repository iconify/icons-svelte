<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcsvi2buz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vcsvi2buz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:evil-book" {...props}></Icon>
