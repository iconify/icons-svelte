<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu2a-wbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hu2a-wbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:grabber-dots" {...props}></Icon>
