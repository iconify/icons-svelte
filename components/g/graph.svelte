<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8vg3ubnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":648};
const content = `<path class="e8vg3ubnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:graph" {...props}></Icon>
