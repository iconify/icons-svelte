<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6u24bczz.css';
import '../../css/k/k15odkf_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j6u24bczz"/><path class="k15odkf_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:project-roadmap-16" {...props}></Icon>
