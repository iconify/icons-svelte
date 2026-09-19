<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsj0y6bqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xsj0y6bqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:flow-data" {...props}></Icon>
