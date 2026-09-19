<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwa2rfbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwa2rfbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:milk-bottle" {...props}></Icon>
