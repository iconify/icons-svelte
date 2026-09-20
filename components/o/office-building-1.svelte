<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqubr3bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xqubr3bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:office-building-1" {...props}></Icon>
