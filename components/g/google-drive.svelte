<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8dmnm1kf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z8dmnm1kf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:google-drive" {...props}></Icon>
