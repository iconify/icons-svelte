<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd5g40bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yd5g40bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:diskover-dark" {...props}></Icon>
