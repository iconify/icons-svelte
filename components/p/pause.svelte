<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5o7gfw9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":384};
const content = `<path class="t5o7gfw9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:pause" {...props}></Icon>
