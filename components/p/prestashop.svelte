<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c72l8qbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="c72l8qbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:prestashop" {...props}></Icon>
