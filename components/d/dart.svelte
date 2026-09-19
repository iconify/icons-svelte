<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajb6qbcvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ajb6qbcvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dart" {...props}></Icon>
