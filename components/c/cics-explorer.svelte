<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1xa-73rj.css';
import '../../css/s/svdy80z7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x1xa-73rj"/><path class="svdy80z7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cics-explorer" {...props}></Icon>
