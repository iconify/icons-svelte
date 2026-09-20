<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gof9z4p8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gof9z4p8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hubspot" {...props}></Icon>
