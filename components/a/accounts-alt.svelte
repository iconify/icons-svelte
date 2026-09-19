<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1jd9vhko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="y1jd9vhko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:accounts-alt" {...props}></Icon>
