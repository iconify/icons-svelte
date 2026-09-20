<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou99r_79m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ou99r_79m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:box-refresh-outline" {...props}></Icon>
