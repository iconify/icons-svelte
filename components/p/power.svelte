<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr6itxbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr6itxbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:power" {...props}></Icon>
