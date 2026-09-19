<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4g5dwuee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="z4g5dwuee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:hearts-card" {...props}></Icon>
