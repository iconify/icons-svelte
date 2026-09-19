<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua_ilqy1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ua_ilqy1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-location-plus" {...props}></Icon>
