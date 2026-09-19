<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/viimxnb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="viimxnb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:border-style" {...props}></Icon>
