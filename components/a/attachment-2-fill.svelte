<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo6cm4bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qo6cm4bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:attachment-2-fill" {...props}></Icon>
