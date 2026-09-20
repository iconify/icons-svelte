<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uss3lth2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uss3lth2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pause-small-outline" {...props}></Icon>
