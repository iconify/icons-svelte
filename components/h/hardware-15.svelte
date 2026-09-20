<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w17b5e_rt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w17b5e_rt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:hardware-15" {...props}></Icon>
