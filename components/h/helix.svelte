<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9wmkvbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="e9wmkvbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:helix" {...props}></Icon>
