<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erhfpqflh.css';
import '../../css/r/r8c016bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erhfpqflh"/><path class="r8c016bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:filter-close-outline" {...props}></Icon>
