<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ueti9nbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ueti9nbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:dropper-outline" {...props}></Icon>
