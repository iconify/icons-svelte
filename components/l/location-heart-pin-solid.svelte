<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4oc5bcrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z4oc5bcrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:location-heart-pin-solid" {...props}></Icon>
