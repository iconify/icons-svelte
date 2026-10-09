<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emvwi1bcs.css';
import '../../css/f/f-3_hbcnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="emvwi1bcs"/><path class="f-3_hbcnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-left-to-line-20-bold" {...props}></Icon>
