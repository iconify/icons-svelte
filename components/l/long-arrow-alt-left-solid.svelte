<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcjsrx5uw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vcjsrx5uw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:long-arrow-alt-left-solid" {...props}></Icon>
