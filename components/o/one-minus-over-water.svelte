<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs3xk0brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hs3xk0brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:one-minus-over-water" {...props}></Icon>
