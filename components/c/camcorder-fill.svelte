<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx2cq-bjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zx2cq-bjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camcorder-fill" {...props}></Icon>
