<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz6id2bed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xz6id2bed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:equalizer" {...props}></Icon>
