<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fibqiob8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fibqiob8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-bottom-left-bold-box-outline" {...props}></Icon>
