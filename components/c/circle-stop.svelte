<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gic3z1hlp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gic3z1hlp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:circle-stop" {...props}></Icon>
