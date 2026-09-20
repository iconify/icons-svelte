<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdn6n-b6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bdn6n-b6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:long-arrow-alt-right-solid" {...props}></Icon>
