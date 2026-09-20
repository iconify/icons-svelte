<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-heh5bgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z-heh5bgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:caravan" {...props}></Icon>
