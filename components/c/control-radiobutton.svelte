<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhto3bqyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uhto3bqyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:control-radiobutton" {...props}></Icon>
