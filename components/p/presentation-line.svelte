<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc15d8b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nc15d8b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:presentation-line" {...props}></Icon>
