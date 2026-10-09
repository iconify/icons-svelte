<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_695na3e.css';
import '../../css/b/b3-608noy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k_695na3e"/><path class="b3-608noy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-island-20-bold" {...props}></Icon>
