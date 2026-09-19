<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhqe3lmxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="xhqe3lmxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:align-left" {...props}></Icon>
