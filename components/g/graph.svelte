<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzry5qg5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="dzry5qg5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:graph" {...props}></Icon>
