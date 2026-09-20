<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l20qj3sjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l20qj3sjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bear-spray-can-with-spray-and-pound" {...props}></Icon>
