<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifvm5m-6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifvm5m-6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:lens-convex" {...props}></Icon>
