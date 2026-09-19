<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk68ltbne.css';
import '../../css/a/a0xb5cbaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="nk68ltbne"/><path class="a0xb5cbaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:checkbox" {...props}></Icon>
