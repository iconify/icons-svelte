<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywm2orvft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="ywm2orvft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:dns" {...props}></Icon>
