<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfqmicchz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfqmicchz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cart-plus" {...props}></Icon>
