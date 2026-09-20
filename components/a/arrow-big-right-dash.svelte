<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyqog2bgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyqog2bgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-big-right-dash" {...props}></Icon>
