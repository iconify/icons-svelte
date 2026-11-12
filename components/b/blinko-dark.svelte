<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu0ejsbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gu0ejsbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:blinko-dark" {...props}></Icon>
