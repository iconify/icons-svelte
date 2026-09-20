<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpp5awb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kpp5awb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:male" {...props}></Icon>
