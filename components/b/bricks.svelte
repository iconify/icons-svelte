<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwd_jac5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="xwd_jac5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:bricks" {...props}></Icon>
