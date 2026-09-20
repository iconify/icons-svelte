<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8sxr3vcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8sxr3vcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pen" {...props}></Icon>
