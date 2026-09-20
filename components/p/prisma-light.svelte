<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3m2ftunn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":310};
const content = `<path class="r3m2ftunn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:prisma-light" {...props}></Icon>
