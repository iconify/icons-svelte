<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beuy52btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="beuy52btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:google-scholar" {...props}></Icon>
