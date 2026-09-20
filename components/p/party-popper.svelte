<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1hdf1bgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="e1hdf1bgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:party-popper" {...props}></Icon>
