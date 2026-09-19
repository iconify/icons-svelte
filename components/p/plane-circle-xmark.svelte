<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejwi4yg8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ejwi4yg8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:plane-circle-xmark" {...props}></Icon>
