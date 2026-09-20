<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7yndj7yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":16};
const content = `<path class="y7yndj7yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:code" {...props}></Icon>
