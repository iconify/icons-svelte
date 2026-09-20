<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt8bckbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yt8bckbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bicycle-x-4" {...props}></Icon>
