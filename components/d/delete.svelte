<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwbs4bb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":512};
const content = `<path class="xwbs4bb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:delete" {...props}></Icon>
