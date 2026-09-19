<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1v5_pbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="t1v5_pbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:missedcall" {...props}></Icon>
