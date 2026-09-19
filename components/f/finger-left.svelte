<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj0su9btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vj0su9btl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:finger-left" {...props}></Icon>
