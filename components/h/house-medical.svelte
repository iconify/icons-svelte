<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8t73ccrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="n8t73ccrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:house-medical" {...props}></Icon>
