<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay0q8wp0f.css';
import '../../css/v/v6k4kxbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ay0q8wp0f"/><path class="v6k4kxbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:rocket" {...props}></Icon>
