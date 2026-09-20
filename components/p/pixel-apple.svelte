<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl8oj5rij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gl8oj5rij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-apple" {...props}></Icon>
