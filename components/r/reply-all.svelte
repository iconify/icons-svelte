<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clcn2dq2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1550,"height":1000};
const content = `<path class="clcn2dq2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:reply-all" {...props}></Icon>
