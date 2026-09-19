<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0v9ddlnx.css';
import '../../css/a/a2og3c3yl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0v9ddlnx"/><path class="a2og3c3yl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:moon-star-filled" {...props}></Icon>
