<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7p7ftetp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z7p7ftetp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-bottom-right-beside-arrow-bottom-left-above-arrow-top-right-beside-arrow-top-left" {...props}></Icon>
