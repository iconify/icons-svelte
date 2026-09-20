<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b83i4cbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="b83i4cbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:loop-1-remix" {...props}></Icon>
