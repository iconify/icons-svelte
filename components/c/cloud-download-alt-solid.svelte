<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l73x2db2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l73x2db2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cloud-download-alt-solid" {...props}></Icon>
