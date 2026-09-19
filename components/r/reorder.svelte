<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4-0ybc2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1280};
const content = `<path class="s4-0ybc2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:reorder" {...props}></Icon>
