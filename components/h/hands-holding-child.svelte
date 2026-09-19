<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b23j45yys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="b23j45yys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hands-holding-child" {...props}></Icon>
