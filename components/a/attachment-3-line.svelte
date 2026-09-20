<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhtoks96l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhtoks96l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:attachment-3-line" {...props}></Icon>
