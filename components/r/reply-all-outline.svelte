<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmlb6r02r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmlb6r02r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:reply-all-outline" {...props}></Icon>
