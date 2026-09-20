<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_xr55c6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-7,"top":-2};
const content = `<path class="q_xr55c6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:capsule" {...props}></Icon>
