<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3y366bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k3y366bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:passport-with-belgium" {...props}></Icon>
