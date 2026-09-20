<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4eq_ek3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e4eq_ek3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:pound" {...props}></Icon>
