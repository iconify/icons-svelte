<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o307cpbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o307cpbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:forest" {...props}></Icon>
