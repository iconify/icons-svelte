<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw82a8b6o.css';
import '../../css/u/u048i3bwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fw82a8b6o"/><path class="u048i3bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:opera-solid" {...props}></Icon>
