<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywtwtq1rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywtwtq1rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dental-line" {...props}></Icon>
