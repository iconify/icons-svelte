<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc6opcb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc6opcb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:first-aid-fill-round" {...props}></Icon>
