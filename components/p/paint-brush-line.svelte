<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqzqczbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqzqczbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:paint-brush-line" {...props}></Icon>
