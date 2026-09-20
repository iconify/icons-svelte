<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlmme1c1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlmme1c1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-up-right-from-square" {...props}></Icon>
