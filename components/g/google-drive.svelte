<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwekcm-al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwekcm-al"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:google-drive" {...props}></Icon>
