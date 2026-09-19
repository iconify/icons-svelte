<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq1x3jbtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rq1x3jbtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:rewind-two-x" {...props}></Icon>
