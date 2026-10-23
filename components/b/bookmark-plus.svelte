<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb_4qqbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jb_4qqbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bookmark-plus" {...props}></Icon>
