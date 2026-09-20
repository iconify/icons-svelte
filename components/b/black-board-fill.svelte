<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa-lzd6aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa-lzd6aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:black-board-fill" {...props}></Icon>
