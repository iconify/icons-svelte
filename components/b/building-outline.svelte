<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-ho-bbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="k-ho-bbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:building-outline" {...props}></Icon>
