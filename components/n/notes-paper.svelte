<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8ysajbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q8ysajbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:notes-paper" {...props}></Icon>
