<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkg_-fbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bkg_-fbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:maloja-light" {...props}></Icon>
