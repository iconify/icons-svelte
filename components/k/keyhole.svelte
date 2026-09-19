<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmir8hivb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":1024};
const content = `<path class="dmir8hivb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:keyhole" {...props}></Icon>
