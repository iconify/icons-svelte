<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1vh-bckm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r1vh-bckm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:diamond-1-solid" {...props}></Icon>
