<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p421z3nfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p421z3nfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:drag-vertical-duocolor-round" {...props}></Icon>
