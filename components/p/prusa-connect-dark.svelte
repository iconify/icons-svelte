<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe2cyjbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xe2cyjbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:prusa-connect-dark" {...props}></Icon>
