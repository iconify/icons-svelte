<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs2m-5bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qs2m-5bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:happycow" {...props}></Icon>
