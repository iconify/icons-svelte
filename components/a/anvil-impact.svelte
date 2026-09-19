<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd1w1xrrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fd1w1xrrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:anvil-impact" {...props}></Icon>
