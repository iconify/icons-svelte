<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1m3h6bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="m1m3h6bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:explosion" {...props}></Icon>
