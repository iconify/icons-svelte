<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om7c014xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="om7c014xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-euro" {...props}></Icon>
