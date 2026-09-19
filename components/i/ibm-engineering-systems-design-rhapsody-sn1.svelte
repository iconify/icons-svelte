<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g75be7uzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g75be7uzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-engineering-systems-design-rhapsody-sn1" {...props}></Icon>
