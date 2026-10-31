<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly6e73blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly6e73blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-chevron-down-gloss" {...props}></Icon>
