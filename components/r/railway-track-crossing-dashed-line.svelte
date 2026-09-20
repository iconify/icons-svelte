<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3t3gjbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b3t3gjbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:railway-track-crossing-dashed-line" {...props}></Icon>
