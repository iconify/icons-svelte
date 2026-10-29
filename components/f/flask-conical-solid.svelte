<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrr6zx6_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrr6zx6_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:flask-conical-solid" {...props}></Icon>
