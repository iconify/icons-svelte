<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r34k3ubvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="r34k3ubvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:center-fill-12" {...props}></Icon>
