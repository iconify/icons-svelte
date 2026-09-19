<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgn0limsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="jgn0limsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:circle-line-fill-12" {...props}></Icon>
