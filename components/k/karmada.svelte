<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/coj7f6n0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":220.61,"height":173.65};
const content = `<path class="coj7f6n0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:karmada" {...props}></Icon>
