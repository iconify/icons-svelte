<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-1xrybxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="j-1xrybxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hands" {...props}></Icon>
