<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g55q6onat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g55q6onat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:map-outline" {...props}></Icon>
