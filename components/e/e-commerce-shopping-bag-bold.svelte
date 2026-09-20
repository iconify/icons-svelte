<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksr103b_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksr103b_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:e-commerce-shopping-bag-bold" {...props}></Icon>
