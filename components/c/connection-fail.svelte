<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdk8769xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="hdk8769xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:connection-fail" {...props}></Icon>
