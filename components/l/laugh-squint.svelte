<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik69wfwmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="ik69wfwmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:laugh-squint" {...props}></Icon>
