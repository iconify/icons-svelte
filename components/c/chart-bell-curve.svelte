<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xatenq_en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xatenq_en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chart-bell-curve" {...props}></Icon>
