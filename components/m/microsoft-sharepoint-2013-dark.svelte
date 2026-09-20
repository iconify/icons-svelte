<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0k-_7b6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j0k-_7b6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-sharepoint-2013-dark" {...props}></Icon>
