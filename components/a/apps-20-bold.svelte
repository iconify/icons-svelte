<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j23gzxbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j23gzxbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:apps-20-bold" {...props}></Icon>
