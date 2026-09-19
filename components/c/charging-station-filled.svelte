<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu6inrb8q.css';
import '../../css/o/o4p12ib8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gu6inrb8q"/><path class="o4p12ib8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:charging-station-filled" {...props}></Icon>
