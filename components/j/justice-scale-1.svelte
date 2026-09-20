<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btq4q2n4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="btq4q2n4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:justice-scale-1" {...props}></Icon>
