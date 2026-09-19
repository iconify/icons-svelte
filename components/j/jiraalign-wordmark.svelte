<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbgysbc5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jbgysbc5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:jiraalign-wordmark" {...props}></Icon>
