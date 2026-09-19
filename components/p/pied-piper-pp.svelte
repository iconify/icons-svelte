<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw7jycbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="gw7jycbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:pied-piper-pp" {...props}></Icon>
