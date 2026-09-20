<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo2i2uwbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wo2i2uwbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:flask-solid" {...props}></Icon>
