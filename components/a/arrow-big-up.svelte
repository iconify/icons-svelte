<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik0528buj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ik0528buj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-big-up" {...props}></Icon>
