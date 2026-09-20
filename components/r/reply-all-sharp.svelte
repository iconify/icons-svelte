<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxh_3sbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxh_3sbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:reply-all-sharp" {...props}></Icon>
