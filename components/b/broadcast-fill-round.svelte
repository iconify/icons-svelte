<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zchyagkzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zchyagkzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:broadcast-fill-round" {...props}></Icon>
