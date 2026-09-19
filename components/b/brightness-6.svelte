<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4djnsbwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":488,"height":496};
const content = `<path class="y4djnsbwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:brightness-6" {...props}></Icon>
