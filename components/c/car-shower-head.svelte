<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7jaokete.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n7jaokete"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:car-shower-head" {...props}></Icon>
