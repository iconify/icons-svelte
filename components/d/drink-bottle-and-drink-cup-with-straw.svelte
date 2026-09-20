<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cniwqxb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cniwqxb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:drink-bottle-and-drink-cup-with-straw" {...props}></Icon>
