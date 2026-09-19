<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6ijimd2c.css';
import '../../css/v/vt4x3hbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i6ijimd2c"/><path class="vt4x3hbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:phone-x-mark-16-solid" {...props}></Icon>
