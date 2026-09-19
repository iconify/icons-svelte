<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svy3we4zq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svy3we4zq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:move-h" {...props}></Icon>
