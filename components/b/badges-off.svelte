<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_vx9acpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_vx9acpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:badges-off" {...props}></Icon>
