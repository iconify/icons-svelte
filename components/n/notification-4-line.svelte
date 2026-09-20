<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slehs114y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slehs114y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:notification-4-line" {...props}></Icon>
