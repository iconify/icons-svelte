<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeo6ylbip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xeo6ylbip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:draw-behind-filled" {...props}></Icon>
