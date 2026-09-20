<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw11f-2rp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uw11f-2rp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:motorcycle" {...props}></Icon>
