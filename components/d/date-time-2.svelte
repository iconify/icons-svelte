<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij0d9-bay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ij0d9-bay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:date-time-2" {...props}></Icon>
