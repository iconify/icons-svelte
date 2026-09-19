<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxqr9heyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sxqr9heyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:homify" {...props}></Icon>
