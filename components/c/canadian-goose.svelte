<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq0j-ab4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nq0j-ab4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:canadian-goose" {...props}></Icon>
