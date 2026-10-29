<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs-s1wbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zs-s1wbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:minus-solid" {...props}></Icon>
