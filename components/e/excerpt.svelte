<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il40rye5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="il40rye5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:excerpt" {...props}></Icon>
