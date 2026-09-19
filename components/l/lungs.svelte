<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnk5bhbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="fnk5bhbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:lungs" {...props}></Icon>
