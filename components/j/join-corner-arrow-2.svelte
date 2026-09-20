<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q__bsmjwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q__bsmjwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:join-corner-arrow-2" {...props}></Icon>
