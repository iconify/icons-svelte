<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxzmh491c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="oxzmh491c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:prolog-wordmark" {...props}></Icon>
