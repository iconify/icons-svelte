<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vazhz5-2p.css';
import '../../css/a/auct0ubxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="vazhz5-2p"/><path class="auct0ubxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:money-location" {...props}></Icon>
