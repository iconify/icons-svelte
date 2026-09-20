<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cswy7ackf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cswy7ackf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:h" {...props}></Icon>
