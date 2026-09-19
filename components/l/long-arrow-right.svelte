<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbcloqqar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="tbcloqqar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:long-arrow-right" {...props}></Icon>
