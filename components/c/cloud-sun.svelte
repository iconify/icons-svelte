<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi-r9sb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi-r9sb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloud-sun" {...props}></Icon>
