<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgoazubgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pgoazubgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:building2-filled" {...props}></Icon>
