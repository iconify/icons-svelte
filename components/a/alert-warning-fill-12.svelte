<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i136-euic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="i136-euic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:alert-warning-fill-12" {...props}></Icon>
