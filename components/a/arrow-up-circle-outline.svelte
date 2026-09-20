<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpu1kzy3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zpu1kzy3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-up-circle-outline" {...props}></Icon>
