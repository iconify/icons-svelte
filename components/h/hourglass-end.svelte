<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqhyvdoxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="hqhyvdoxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hourglass-end" {...props}></Icon>
