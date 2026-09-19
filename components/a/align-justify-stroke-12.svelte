<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqd_e4bob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="iqd_e4bob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:align-justify-stroke-12" {...props}></Icon>
