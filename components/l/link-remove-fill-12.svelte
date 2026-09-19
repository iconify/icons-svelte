<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4f9te_7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="q4f9te_7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:link-remove-fill-12" {...props}></Icon>
