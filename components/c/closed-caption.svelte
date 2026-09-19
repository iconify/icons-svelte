<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4m5ftbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="u4m5ftbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:closed-caption" {...props}></Icon>
