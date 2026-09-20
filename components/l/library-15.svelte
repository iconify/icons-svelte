<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ey4_sobig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ey4_sobig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:library-15" {...props}></Icon>
