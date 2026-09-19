<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7vpkb-dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="x7vpkb-dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:reactbootstrap" {...props}></Icon>
