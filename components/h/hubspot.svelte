<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd9t6vxrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dd9t6vxrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hubspot" {...props}></Icon>
