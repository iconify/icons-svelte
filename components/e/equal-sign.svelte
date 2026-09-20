<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqes0-jyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="bqes0-jyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:equal-sign" {...props}></Icon>
