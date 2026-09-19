<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/makyqeb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="makyqeb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:css3" {...props}></Icon>
