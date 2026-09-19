<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsvaxh48l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rsvaxh48l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-medical-fill" {...props}></Icon>
