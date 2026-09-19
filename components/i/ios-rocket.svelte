<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5cimwbxh.css';
import '../../css/m/mnxsi_e-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x5cimwbxh"/><path class="mnxsi_e-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-rocket" {...props}></Icon>
