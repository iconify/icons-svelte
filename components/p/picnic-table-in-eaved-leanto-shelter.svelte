<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr938p2vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yr938p2vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:picnic-table-in-eaved-leanto-shelter" {...props}></Icon>
