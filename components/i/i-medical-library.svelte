<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lked-oz3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="lked-oz3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-medical-library" {...props}></Icon>
