<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi7wnx1bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mi7wnx1bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openpanel-light" {...props}></Icon>
