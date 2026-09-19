<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnl2rfb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="gnl2rfb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:fedora" {...props}></Icon>
