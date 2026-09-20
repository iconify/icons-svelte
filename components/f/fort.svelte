<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7rltjgme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e7rltjgme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fort" {...props}></Icon>
