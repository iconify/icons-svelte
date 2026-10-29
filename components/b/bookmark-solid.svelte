<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmcm-abnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmcm-abnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bookmark-solid" {...props}></Icon>
