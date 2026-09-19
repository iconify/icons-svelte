<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4ppc7bcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="m4ppc7bcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:globe" {...props}></Icon>
