<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjowf5brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sjowf5brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:icon-pause-music-16" {...props}></Icon>
