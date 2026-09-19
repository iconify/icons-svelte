<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzf-ogtqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wzf-ogtqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-down-on-square-stack" {...props}></Icon>
