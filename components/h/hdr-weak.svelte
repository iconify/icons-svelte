<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2df7obqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="o2df7obqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:hdr-weak" {...props}></Icon>
