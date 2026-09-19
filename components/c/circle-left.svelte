<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6hqopx1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f6hqopx1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:circle-left" {...props}></Icon>
