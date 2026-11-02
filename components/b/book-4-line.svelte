<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unfj3cbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unfj3cbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-4-line" {...props}></Icon>
