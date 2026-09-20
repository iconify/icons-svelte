<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy5eoqe4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qy5eoqe4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:arrow-next-ltr" {...props}></Icon>
