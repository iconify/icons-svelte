<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux1eiccpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux1eiccpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:pause-waves-solid" {...props}></Icon>
