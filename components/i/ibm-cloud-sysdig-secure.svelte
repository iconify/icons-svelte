<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq-0w-box.css';
import '../../css/w/wxyzcrbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iq-0w-box"/><path class="wxyzcrbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-sysdig-secure" {...props}></Icon>
