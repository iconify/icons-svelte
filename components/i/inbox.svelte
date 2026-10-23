<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9rr8kbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9rr8kbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:inbox" {...props}></Icon>
