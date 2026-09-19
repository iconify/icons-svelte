<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikb0k8gli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikb0k8gli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-droplet-half" {...props}></Icon>
