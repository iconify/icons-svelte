<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywytedb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywytedb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:power-meter-outline" {...props}></Icon>
