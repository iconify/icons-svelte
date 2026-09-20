<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebc46_dxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ebc46_dxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:piggy-bank-solid" {...props}></Icon>
