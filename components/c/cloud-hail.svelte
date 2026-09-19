<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyghp1une.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dyghp1une"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-hail" {...props}></Icon>
