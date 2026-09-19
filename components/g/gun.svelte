<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1tu19bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g1tu19bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:gun" {...props}></Icon>
