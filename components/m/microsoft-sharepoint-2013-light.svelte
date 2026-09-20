<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dh4zwjb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dh4zwjb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-sharepoint-2013-light" {...props}></Icon>
