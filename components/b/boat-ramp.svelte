<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5qcd1b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="j5qcd1b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:boat-ramp" {...props}></Icon>
