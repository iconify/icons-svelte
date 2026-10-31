<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c16u-3bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c16u-3bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-uturn-down-right" {...props}></Icon>
