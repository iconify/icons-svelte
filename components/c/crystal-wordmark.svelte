<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmo_f7bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lmo_f7bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:crystal-wordmark" {...props}></Icon>
