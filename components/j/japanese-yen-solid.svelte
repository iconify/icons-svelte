<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tz1y301ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tz1y301ju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:japanese-yen-solid" {...props}></Icon>
