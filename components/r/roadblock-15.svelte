<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm3dusb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gm3dusb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:roadblock-15" {...props}></Icon>
