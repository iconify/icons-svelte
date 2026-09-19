<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj6e5wb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aj6e5wb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:forward" {...props}></Icon>
