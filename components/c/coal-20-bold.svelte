<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p181rzbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p181rzbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coal-20-bold" {...props}></Icon>
