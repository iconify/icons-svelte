<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzhxep-4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fzhxep-4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:battery-0" {...props}></Icon>
