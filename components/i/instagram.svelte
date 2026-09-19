<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9npbdcjc.css';
import '../../css/d/d8axicc0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9npbdcjc"/><path class="d8axicc0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:instagram" {...props}></Icon>
