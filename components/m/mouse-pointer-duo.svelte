<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzkqyibmp.css';
import '../../css/g/g768bfbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzkqyibmp secondary"/><path class="g768bfbwz primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mouse-pointer-duo" {...props}></Icon>
