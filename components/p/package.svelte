<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufbk1cboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ufbk1cboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:package" {...props}></Icon>
