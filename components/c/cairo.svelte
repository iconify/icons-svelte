<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtgxhbc5g.css';
import '../../css/u/uidnkmboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vtgxhbc5g"/><path class="uidnkmboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:cairo" {...props}></Icon>
