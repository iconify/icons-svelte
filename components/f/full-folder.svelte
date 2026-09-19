<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9d64bbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a9d64bbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:full-folder" {...props}></Icon>
