<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsqr_kr0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="rsqr_kr0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:luau" {...props}></Icon>
