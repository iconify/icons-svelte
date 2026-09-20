<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrlen5bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrlen5bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bugle" {...props}></Icon>
