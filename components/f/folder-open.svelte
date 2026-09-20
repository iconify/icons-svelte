<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qh1fr4b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qh1fr4b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:folder-open" {...props}></Icon>
