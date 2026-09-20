<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sznq_fb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sznq_fb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:minus-in-circle-filled" {...props}></Icon>
