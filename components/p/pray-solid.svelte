<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfqb70bbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bfqb70bbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:pray-solid" {...props}></Icon>
