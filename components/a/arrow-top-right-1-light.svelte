<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p22skhu_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p22skhu_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-right-1-light" {...props}></Icon>
