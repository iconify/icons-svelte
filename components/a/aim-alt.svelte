<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq1ofbodp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="lq1ofbodp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:aim-alt" {...props}></Icon>
