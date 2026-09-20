<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upnywkbgf.css';
import '../../css/v/vssr6lrmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upnywkbgf"/><path class="vssr6lrmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:chield-duotone" {...props}></Icon>
