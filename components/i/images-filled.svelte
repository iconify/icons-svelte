<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqygs8_op.css';
import '../../css/b/bog62tbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqygs8_op"/><path class="bog62tbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:images-filled" {...props}></Icon>
