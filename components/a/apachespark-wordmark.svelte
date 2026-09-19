<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9w77bbrk.css';
import '../../css/z/zbefq9b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="c9w77bbrk"/><path class="zbefq9b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:apachespark-wordmark" {...props}></Icon>
