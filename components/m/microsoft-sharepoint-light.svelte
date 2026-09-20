<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3k6m-bgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v3k6m-bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-sharepoint-light" {...props}></Icon>
