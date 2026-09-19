<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7bclh6ay.css';
import '../../css/e/e9s0ab8fq.css';
import '../../css/y/y8uolzsot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="y7bclh6ay"/><path class="e9s0ab8fq"/><path class="y8uolzsot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:phone-route-alt-r" {...props}></Icon>
