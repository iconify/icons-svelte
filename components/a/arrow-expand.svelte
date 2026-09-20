<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm-2io57o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wm-2io57o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:arrow-expand" {...props}></Icon>
