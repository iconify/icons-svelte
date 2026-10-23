<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd-0mbc3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd-0mbc3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:rocket" {...props}></Icon>
