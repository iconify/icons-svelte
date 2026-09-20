<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cho2ybc2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cho2ybc2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rectangle-tall-outline" {...props}></Icon>
