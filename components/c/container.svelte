<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxc0iqbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxc0iqbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:container" {...props}></Icon>
