<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otza0daer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="otza0daer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:blinko-light" {...props}></Icon>
