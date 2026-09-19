<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtr2jecan.css';
import '../../css/y/yt81ngblg.css';
import '../../css/f/fkatt9b7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":14};
const content = `<path class="wtr2jecan"/><path class="yt81ngblg"/><path class="fkatt9b7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:downloadcloud" {...props}></Icon>
