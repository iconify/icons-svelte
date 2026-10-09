<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpv1dkbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hpv1dkbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:barcode-48-bold" {...props}></Icon>
