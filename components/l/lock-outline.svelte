<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgh2i2xsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mgh2i2xsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:lock-outline" {...props}></Icon>
