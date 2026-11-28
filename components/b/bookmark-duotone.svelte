<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqpcb34im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary wqpcb34im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bookmark-duotone" {...props}></Icon>
