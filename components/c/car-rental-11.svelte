<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdepvubof.css';
import '../../css/a/aynajtbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="vdepvubof"/><path class="aynajtbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:car-rental-11" {...props}></Icon>
