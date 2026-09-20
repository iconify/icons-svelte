<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7uz5csis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j7uz5csis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:roman-numeral-iii" {...props}></Icon>
