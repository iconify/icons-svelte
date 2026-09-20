<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x41chim9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x41chim9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:ember" {...props}></Icon>
