<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb3137b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zb3137b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:junie-wordmark" {...props}></Icon>
