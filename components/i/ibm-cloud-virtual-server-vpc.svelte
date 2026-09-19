<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-cigyqaj.css';
import '../../css/d/dmmzmkb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="o-cigyqaj"/><path class="dmmzmkb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-cloud-virtual-server-vpc" {...props}></Icon>
