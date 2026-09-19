<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7agvlggf.css';
import '../../css/j/jkzqgictx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="k7agvlggf"/><path class="jkzqgictx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:neo4j-wordmark" {...props}></Icon>
