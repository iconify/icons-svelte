<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqvvaebnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqvvaebnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-search-corner-round" {...props}></Icon>
