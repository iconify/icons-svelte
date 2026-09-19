<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl9sn23sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hl9sn23sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:openstack" {...props}></Icon>
