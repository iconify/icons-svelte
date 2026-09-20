<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x55li5b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x55li5b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:ellipsis" {...props}></Icon>
