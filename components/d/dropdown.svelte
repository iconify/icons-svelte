<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rup5qzhbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":616,"height":614};
const content = `<path class="rup5qzhbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:dropdown" {...props}></Icon>
