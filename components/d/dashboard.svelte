<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw2mo3r6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":700,"height":700};
const content = `<path class="gw2mo3r6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:dashboard" {...props}></Icon>
