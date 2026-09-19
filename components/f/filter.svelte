<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rro1-sbje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":472};
const content = `<path class="rro1-sbje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:filter" {...props}></Icon>
