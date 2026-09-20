<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssvlisb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ssvlisb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:aperture" {...props}></Icon>
