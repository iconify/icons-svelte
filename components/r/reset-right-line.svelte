<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynf38iw_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynf38iw_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:reset-right-line" {...props}></Icon>
