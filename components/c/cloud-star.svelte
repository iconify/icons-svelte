<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-t-o1ivl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-t-o1ivl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cloud-star" {...props}></Icon>
