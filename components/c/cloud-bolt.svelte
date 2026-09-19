<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc510tt4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fc510tt4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cloud-bolt" {...props}></Icon>
