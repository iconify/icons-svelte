<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5gc8fbdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="x5gc8fbdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:leaf-stroke-12" {...props}></Icon>
