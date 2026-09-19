<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoa89xbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="xoa89xbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:minus-sign" {...props}></Icon>
