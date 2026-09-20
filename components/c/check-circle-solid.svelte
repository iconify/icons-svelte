<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl3_1h40s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vl3_1h40s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:check-circle-solid" {...props}></Icon>
