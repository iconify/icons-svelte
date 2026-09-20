<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elr6iiype.css';
import '../../css/c/cycdfo7sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="elr6iiype"/><path class="cycdfo7sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:ai-hand" {...props}></Icon>
