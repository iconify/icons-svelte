<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrf_klbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrf_klbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:cooker-extract-off" {...props}></Icon>
