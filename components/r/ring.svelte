<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqruxjb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iqruxjb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:ring" {...props}></Icon>
