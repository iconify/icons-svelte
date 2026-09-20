<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue95yqnpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ue95yqnpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:ontology-filled" {...props}></Icon>
