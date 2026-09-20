<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zptxq6btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zptxq6btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:landscape" {...props}></Icon>
