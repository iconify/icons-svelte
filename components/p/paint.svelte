<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g698s6blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g698s6blt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:paint" {...props}></Icon>
