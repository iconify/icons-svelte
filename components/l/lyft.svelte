<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn2wu3b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rn2wu3b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:lyft" {...props}></Icon>
