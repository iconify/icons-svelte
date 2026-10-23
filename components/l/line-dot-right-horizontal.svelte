<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7fa6mi_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7fa6mi_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:line-dot-right-horizontal" {...props}></Icon>
