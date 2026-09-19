<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0d5-18fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b0d5-18fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:map" {...props}></Icon>
