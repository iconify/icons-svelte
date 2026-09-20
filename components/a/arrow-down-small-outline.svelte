<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmnc7rkzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cmnc7rkzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-down-small-outline" {...props}></Icon>
