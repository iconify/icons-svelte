<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsn627f2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zsn627f2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:moon-new-fill" {...props}></Icon>
