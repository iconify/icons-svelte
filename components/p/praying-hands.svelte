<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j93twdbsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="j93twdbsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:praying-hands" {...props}></Icon>
