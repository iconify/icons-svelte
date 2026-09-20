<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opwx81bno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="opwx81bno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:garden-center-11" {...props}></Icon>
