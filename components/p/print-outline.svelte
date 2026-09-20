<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9cbzdsar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y9cbzdsar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:print-outline" {...props}></Icon>
