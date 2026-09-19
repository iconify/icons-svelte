<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i242pgvho.css';
import '../../css/i/ijptld2hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="i242pgvho"/><path class="ijptld2hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:junit" {...props}></Icon>
