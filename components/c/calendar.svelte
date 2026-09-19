<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f26qfobhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f26qfobhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:calendar" {...props}></Icon>
