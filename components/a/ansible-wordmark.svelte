<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x120vrb5q.css';
import '../../css/t/tl5abbc0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="x120vrb5q"/><path class="tl5abbc0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:ansible-wordmark" {...props}></Icon>
