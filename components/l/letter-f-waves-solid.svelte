<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze2r_i9qx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ze2r_i9qx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-f-waves-solid" {...props}></Icon>
