<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vsr7h_7_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vsr7h_7_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:facebook" {...props}></Icon>
