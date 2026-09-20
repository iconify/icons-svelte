<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7app61-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e7app61-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-classical-building" {...props}></Icon>
