<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aytrg018o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aytrg018o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:columns-2-line" {...props}></Icon>
