<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv93zobeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vv93zobeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-big-down-bulk-round" {...props}></Icon>
