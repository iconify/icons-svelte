<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-w1fivvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-w1fivvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:restaurant-fill" {...props}></Icon>
