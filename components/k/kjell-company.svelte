<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwvob5sdf.css';
import '../../css/m/m23pw1bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zwvob5sdf"/><path class="m23pw1bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kjell-company" {...props}></Icon>
