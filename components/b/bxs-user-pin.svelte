<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq-zovx8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xq-zovx8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-user-pin" {...props}></Icon>
