<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpg9xubhg.css';
import '../../css/y/y4dz8u3sm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fpg9xubhg"/><path class="y4dz8u3sm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:quality-1-16" {...props}></Icon>
