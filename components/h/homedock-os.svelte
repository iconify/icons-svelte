<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn33j1the.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vn33j1the"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:homedock-os" {...props}></Icon>
