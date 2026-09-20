<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j791lm_cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j791lm_cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:map-signs-solid" {...props}></Icon>
