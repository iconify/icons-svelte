<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh42j-28c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh42j-28c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-down-right" {...props}></Icon>
