<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usss4-bhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="usss4-bhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:flag-checkered" {...props}></Icon>
