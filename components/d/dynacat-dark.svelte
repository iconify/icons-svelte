<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhr1z4b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nhr1z4b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dynacat-dark" {...props}></Icon>
