<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi323x62o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi323x62o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bluetooth-off" {...props}></Icon>
