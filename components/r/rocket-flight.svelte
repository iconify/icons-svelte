<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7sox82ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p7sox82ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rocket-flight" {...props}></Icon>
