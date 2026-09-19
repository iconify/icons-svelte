<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay3y2jkpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ay3y2jkpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:eyepatch" {...props}></Icon>
