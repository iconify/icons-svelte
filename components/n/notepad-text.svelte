<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt3dn4bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qt3dn4bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:notepad-text" {...props}></Icon>
