<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4btbacjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l4btbacjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:reverbnation" {...props}></Icon>
