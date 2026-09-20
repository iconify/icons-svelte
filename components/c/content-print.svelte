<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwf0k67yb.css';
import '../../css/o/o94p-i96p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jwf0k67yb"/><path class="o94p-i96p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-print" {...props}></Icon>
