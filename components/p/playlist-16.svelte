<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwe2b1h6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iwe2b1h6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:playlist-16" {...props}></Icon>
