<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azd3_ibmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azd3_ibmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-u-right-top" {...props}></Icon>
