<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz529hc7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dz529hc7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:key-fill" {...props}></Icon>
