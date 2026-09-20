<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hft_ef9qv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hft_ef9qv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:info" {...props}></Icon>
