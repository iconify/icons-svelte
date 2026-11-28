<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp7d6dfdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp7d6dfdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bracket-right-duo" {...props}></Icon>
