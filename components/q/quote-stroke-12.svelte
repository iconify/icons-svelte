<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9_ht237o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="y9_ht237o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:quote-stroke-12" {...props}></Icon>
