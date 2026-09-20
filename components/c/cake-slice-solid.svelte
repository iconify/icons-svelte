<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyz19x35s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gyz19x35s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cake-slice-solid" {...props}></Icon>
