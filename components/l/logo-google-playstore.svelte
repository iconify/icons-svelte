<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cw26yhbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cw26yhbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-google-playstore" {...props}></Icon>
