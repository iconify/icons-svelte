<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrvc_wb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rrvc_wb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:merge-request-open" {...props}></Icon>
