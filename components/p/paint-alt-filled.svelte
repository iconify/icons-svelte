<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygigg_h9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygigg_h9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:paint-alt-filled" {...props}></Icon>
