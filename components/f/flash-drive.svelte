<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh0zqjb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mh0zqjb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:flash-drive" {...props}></Icon>
