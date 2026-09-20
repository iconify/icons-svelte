<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byytx_lbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="byytx_lbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-text-fast-outline" {...props}></Icon>
