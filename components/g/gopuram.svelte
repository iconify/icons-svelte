<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqzx1_bnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lqzx1_bnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:gopuram" {...props}></Icon>
