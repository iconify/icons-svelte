<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s32cdob1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s32cdob1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:panel-left-fill-round" {...props}></Icon>
