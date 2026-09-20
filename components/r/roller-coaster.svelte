<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhwxgnbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rhwxgnbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:roller-coaster" {...props}></Icon>
