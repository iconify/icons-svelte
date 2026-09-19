<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anky5vblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="anky5vblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:die-face6-small-filled" {...props}></Icon>
