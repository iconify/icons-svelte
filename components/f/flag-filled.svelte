<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh7wynb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sh7wynb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:flag-filled" {...props}></Icon>
