<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5ip8yb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":420,"height":810};
const content = `<path class="r5ip8yb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:mobile" {...props}></Icon>
