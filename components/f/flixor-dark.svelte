<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udeylcb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="udeylcb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flixor-dark" {...props}></Icon>
