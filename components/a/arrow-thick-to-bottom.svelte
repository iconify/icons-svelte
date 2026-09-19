<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk3dn9a9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fk3dn9a9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:arrow-thick-to-bottom" {...props}></Icon>
