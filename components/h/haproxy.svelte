<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc4s4wbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lc4s4wbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:haproxy" {...props}></Icon>
