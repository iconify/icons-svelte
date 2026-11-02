<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqmgsn7hu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqmgsn7hu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chevrons-left-right-ellipsis-line" {...props}></Icon>
