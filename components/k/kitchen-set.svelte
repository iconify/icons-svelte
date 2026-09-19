<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j506mmb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="j506mmb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:kitchen-set" {...props}></Icon>
