<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr1n1y8wn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1,"top":-1};
const content = `<path class="vr1n1y8wn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:flashlight-on-f" {...props}></Icon>
