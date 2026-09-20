<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwmzdrboq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rwmzdrboq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-edit-flip-horizontal-2-arrow-design-flip-reflect" {...props}></Icon>
