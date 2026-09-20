<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn55p_bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zn55p_bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:book-2-line" {...props}></Icon>
