<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8jxx8lwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8jxx8lwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-zip-line" {...props}></Icon>
