<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm76dsbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wm76dsbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filedrop" {...props}></Icon>
