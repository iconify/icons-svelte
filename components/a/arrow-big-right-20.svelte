<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2hg3_40q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u2hg3_40q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-big-right-20" {...props}></Icon>
