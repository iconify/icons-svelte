<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hages2bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hages2bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cart-add" {...props}></Icon>
