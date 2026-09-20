<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqmxrybbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-1};
const content = `<path class="zqmxrybbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:candle" {...props}></Icon>
