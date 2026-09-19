<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcklypb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vcklypb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:financial-mirrored-solid" {...props}></Icon>
