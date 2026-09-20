<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwxucrbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rwxucrbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:board-gondola-lift" {...props}></Icon>
