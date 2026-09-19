<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc8luvptp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="zc8luvptp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:harbor-wordmark" {...props}></Icon>
