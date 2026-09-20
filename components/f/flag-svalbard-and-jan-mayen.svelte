<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8cxt48ie.css';
import '../../css/n/nn54hsble.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="e8cxt48ie"/><path class="nn54hsble"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-svalbard-and-jan-mayen" {...props}></Icon>
