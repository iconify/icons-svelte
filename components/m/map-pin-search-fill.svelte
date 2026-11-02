<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq9y-x28s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tq9y-x28s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-pin-search-fill" {...props}></Icon>
