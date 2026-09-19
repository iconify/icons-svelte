<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz1up0bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="wz1up0bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:earth-australia-o" {...props}></Icon>
