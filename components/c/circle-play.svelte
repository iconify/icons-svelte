<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5qi_xc7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c5qi_xc7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:circle-play" {...props}></Icon>
