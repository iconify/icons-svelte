<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgobatyfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="xgobatyfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:heliport-11" {...props}></Icon>
