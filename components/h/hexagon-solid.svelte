<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqjs_6btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nqjs_6btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:hexagon-solid" {...props}></Icon>
