<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3w5-xb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="b3w5-xb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:center-focus-strong" {...props}></Icon>
