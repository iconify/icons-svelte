<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcpul5bqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcpul5bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:flashlight-x" {...props}></Icon>
