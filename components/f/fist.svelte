<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdwl95bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hdwl95bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:fist" {...props}></Icon>
