<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a553rmbqh.css';
import '../../css/g/ga-aabcqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a553rmbqh"/><path class="ga-aabcqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-arrow-left-bold-duotone" {...props}></Icon>
