<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_7j9fb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a_7j9fb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:connector-hex" {...props}></Icon>
