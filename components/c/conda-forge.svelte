<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp_b1m3ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bp_b1m3ik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:conda-forge" {...props}></Icon>
