<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmjxt8bcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmjxt8bcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-more-fill" {...props}></Icon>
