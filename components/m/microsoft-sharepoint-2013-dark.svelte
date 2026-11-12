<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwkk4acjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hwkk4acjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-sharepoint-2013-dark" {...props}></Icon>
