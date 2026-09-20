<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj7790gly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aj7790gly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:data-type-string" {...props}></Icon>
