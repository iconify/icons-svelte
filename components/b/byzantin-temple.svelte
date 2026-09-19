<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crf5lachd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="crf5lachd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:byzantin-temple" {...props}></Icon>
