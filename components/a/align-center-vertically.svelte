<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4z96hb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="p4z96hb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:align-center-vertically" {...props}></Icon>
