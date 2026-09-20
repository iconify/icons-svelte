<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_n7etb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b_n7etb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lighthouse" {...props}></Icon>
