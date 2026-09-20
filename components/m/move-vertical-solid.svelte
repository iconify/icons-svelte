<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cegq8hbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cegq8hbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:move-vertical-solid" {...props}></Icon>
