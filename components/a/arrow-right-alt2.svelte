<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j31ltebnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j31ltebnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:arrow-right-alt2" {...props}></Icon>
