<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_kglfpln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x_kglfpln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fish-under-water" {...props}></Icon>
