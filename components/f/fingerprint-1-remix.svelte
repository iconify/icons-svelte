<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw91fybat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uw91fybat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:fingerprint-1-remix" {...props}></Icon>
