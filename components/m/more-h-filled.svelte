<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7p1dzbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7p1dzbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:more-h-filled" {...props}></Icon>
