<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5mxaibmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5mxaibmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cloud-download" {...props}></Icon>
