<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjicw-buo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="mjicw-buo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:checkbox-mixed-filled" {...props}></Icon>
