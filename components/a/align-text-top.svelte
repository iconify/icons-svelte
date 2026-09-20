<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjimuib_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yjimuib_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:align-text-top" {...props}></Icon>
