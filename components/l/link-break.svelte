<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opoks_fjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="opoks_fjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:link-break" {...props}></Icon>
