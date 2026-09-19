<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro8s8ib8b.css';
import '../../css/t/terfpnntt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="ro8s8ib8b"/><path class="terfpnntt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:employee-line" {...props}></Icon>
