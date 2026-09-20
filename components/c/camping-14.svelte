<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrefpl81y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="mrefpl81y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:camping-14" {...props}></Icon>
