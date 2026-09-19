<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_2v8v8uq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="i_2v8v8uq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:palette-fill-12" {...props}></Icon>
