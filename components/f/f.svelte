<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jecvu-cad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jecvu-cad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:f" {...props}></Icon>
