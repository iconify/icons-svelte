<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhiafj-by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rhiafj-by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hashicorp-boundary" {...props}></Icon>
