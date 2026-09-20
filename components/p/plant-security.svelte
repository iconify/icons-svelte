<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nge3vp00y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="nge3vp00y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:plant-security" {...props}></Icon>
