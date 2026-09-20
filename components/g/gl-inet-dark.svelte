<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9ds4ubva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o9ds4ubva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gl-inet-dark" {...props}></Icon>
