<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-37_lbpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z-37_lbpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:ontology" {...props}></Icon>
