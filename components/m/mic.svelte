<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9irpyjfv.css';
import '../../css/a/a-5p04cix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a9irpyjfv"/><path class="a-5p04cix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:mic" {...props}></Icon>
