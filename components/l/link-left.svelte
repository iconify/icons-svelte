<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeu03xbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aeu03xbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:link-left" {...props}></Icon>
