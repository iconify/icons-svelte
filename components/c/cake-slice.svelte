<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxea29b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="nxea29b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cake-slice" {...props}></Icon>
