<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6d-ncbcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="n6d-ncbcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:down" {...props}></Icon>
