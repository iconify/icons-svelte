<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsvgvmb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsvgvmb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:octagram-plus" {...props}></Icon>
