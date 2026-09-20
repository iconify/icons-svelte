<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz72bebim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vz72bebim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:1-minus" {...props}></Icon>
