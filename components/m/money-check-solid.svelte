<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4_f801da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s4_f801da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:money-check-solid" {...props}></Icon>
