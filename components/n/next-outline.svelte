<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz-7qynvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rz-7qynvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:next-outline" {...props}></Icon>
