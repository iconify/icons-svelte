<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwj3zabgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lwj3zabgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:print-solid" {...props}></Icon>
