<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkh7_fb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gkh7_fb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:google-drive-solid" {...props}></Icon>
