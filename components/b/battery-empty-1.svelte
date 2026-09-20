<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmhakjb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qmhakjb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:battery-empty-1" {...props}></Icon>
