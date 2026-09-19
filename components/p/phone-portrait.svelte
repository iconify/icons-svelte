<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e00fw2bit.css';
import '../../css/v/vz-n1gf_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<defs><path id="SVGpHmZZbqf" class="e00fw2bit"/></defs><use href="#SVGpHmZZbqf"/><path class="vz-n1gf_b"/><use href="#SVGpHmZZbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:phone-portrait" {...props}></Icon>
