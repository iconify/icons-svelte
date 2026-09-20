<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn5gmacvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pn5gmacvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:bulb" {...props}></Icon>
