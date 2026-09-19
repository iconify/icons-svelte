<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa4eobcfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pa4eobcfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:geocaching" {...props}></Icon>
