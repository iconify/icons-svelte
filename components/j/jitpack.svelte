<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oihh1ccpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oihh1ccpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:jitpack" {...props}></Icon>
