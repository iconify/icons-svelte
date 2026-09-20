<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn5t7vble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kn5t7vble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:geyser" {...props}></Icon>
