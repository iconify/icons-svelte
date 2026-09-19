<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qi1q1kb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qi1q1kb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pouch-with-beads" {...props}></Icon>
