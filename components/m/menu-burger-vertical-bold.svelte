<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrepq8k1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrepq8k1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:menu-burger-vertical-bold" {...props}></Icon>
