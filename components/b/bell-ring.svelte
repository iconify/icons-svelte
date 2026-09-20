<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd2lk3b2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vd2lk3b2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bell-ring" {...props}></Icon>
