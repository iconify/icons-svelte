<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt9z3uuyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dt9z3uuyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-chrome-light" {...props}></Icon>
