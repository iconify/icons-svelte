<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyr3ihb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xyr3ihb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:bluetooth-searching" {...props}></Icon>
