<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t39a96wvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t39a96wvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mp4-outline" {...props}></Icon>
