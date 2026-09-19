<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4ypnxbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f4ypnxbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:circular-saw" {...props}></Icon>
