<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwv-rhboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwv-rhboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-right-up-fill" {...props}></Icon>
