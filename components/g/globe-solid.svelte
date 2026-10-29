<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x01i_ccby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x01i_ccby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:globe-solid" {...props}></Icon>
