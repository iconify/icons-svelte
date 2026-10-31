<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdgb0sbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdgb0sbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:notebook-fill-round" {...props}></Icon>
