<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3rqy3bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w3rqy3bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:dot-circle-solid" {...props}></Icon>
