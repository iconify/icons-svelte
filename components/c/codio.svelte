<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu2424y6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mu2424y6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:codio" {...props}></Icon>
