<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_a5qtbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y_a5qtbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:forward" {...props}></Icon>
