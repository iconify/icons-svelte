<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsdns4anw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsdns4anw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:product-hunt-fill" {...props}></Icon>
