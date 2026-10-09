<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdilgkbdd.css';
import '../../css/f/fqlu4irdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wdilgkbdd"/><path class="fqlu4irdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-up-to-line-20-bold" {...props}></Icon>
