<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz_6fthyk.css';
import '../../css/p/p6qekmbwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bz_6fthyk"/><path class="p6qekmbwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:htmx-wordmark" {...props}></Icon>
