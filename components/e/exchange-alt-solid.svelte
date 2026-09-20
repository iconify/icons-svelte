<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0_rdmbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y0_rdmbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:exchange-alt-solid" {...props}></Icon>
