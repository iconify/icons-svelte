<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oembw3b6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oembw3b6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:kerb-lowered-under-shoe" {...props}></Icon>
