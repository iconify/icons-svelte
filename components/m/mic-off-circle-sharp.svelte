<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yihaffb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yihaffb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:mic-off-circle-sharp" {...props}></Icon>
