<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgxf6ebmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xgxf6ebmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:interlocking-rings-fill-12" {...props}></Icon>
