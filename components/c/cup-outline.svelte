<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q77s72bme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q77s72bme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:cup-outline" {...props}></Icon>
