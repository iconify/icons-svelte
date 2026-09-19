<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf3bt0b5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zf3bt0b5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:enter-fill" {...props}></Icon>
