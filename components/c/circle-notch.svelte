<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5qp_zqit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e5qp_zqit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:circle-notch" {...props}></Icon>
