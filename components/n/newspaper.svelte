<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogjixd8fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ogjixd8fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:newspaper" {...props}></Icon>
