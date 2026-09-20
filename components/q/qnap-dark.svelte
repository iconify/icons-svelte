<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg_08ysvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vg_08ysvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qnap-dark" {...props}></Icon>
