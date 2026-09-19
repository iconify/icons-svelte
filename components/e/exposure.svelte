<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n318iufmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="n318iufmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:exposure" {...props}></Icon>
