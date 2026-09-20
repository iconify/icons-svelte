<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-jrsib1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-jrsib1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:forward-end-line" {...props}></Icon>
