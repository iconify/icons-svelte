<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9cxw4a1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9cxw4a1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:axe-line" {...props}></Icon>
