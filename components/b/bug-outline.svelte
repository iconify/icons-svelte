<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc00nccwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xc00nccwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bug-outline" {...props}></Icon>
