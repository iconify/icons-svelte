<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doos-3v8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="doos-3v8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:question-2-line" {...props}></Icon>
