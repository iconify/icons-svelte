<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db_3tsw-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="db_3tsw-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-teams-2016-light" {...props}></Icon>
