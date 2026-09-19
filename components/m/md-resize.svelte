<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uejs2nbms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uejs2nbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-resize" {...props}></Icon>
