<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caj3s8vnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="caj3s8vnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:door-open" {...props}></Icon>
