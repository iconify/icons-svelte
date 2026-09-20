<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi8q3-b_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hi8q3-b_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hotel-solid" {...props}></Icon>
