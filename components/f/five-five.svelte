<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr8spdb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vr8spdb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:five-five" {...props}></Icon>
