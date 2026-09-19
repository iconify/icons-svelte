<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4lr5punx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="a4lr5punx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:address-card" {...props}></Icon>
