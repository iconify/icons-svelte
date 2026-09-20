<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz-zpsb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nz-zpsb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:anchor-solid" {...props}></Icon>
