<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w686qtbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w686qtbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:bar-graph" {...props}></Icon>
