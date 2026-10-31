<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgk8ipbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgk8ipbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:merge-bulk-round" {...props}></Icon>
