<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr87l9b_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pr87l9b_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-add" {...props}></Icon>
