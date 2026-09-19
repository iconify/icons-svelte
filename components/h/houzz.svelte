<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy8javlss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1792};
const content = `<path class="yy8javlss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:houzz" {...props}></Icon>
