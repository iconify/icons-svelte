<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xao59bcgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xao59bcgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:bell-notification" {...props}></Icon>
