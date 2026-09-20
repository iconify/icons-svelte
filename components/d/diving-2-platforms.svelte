<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvuphu1dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gvuphu1dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:diving-2-platforms" {...props}></Icon>
