<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx0w5hfep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nx0w5hfep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:kerb-flush-under-shoe" {...props}></Icon>
