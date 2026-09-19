<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhls-y5sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1472,"height":1600};
const content = `<path class="bhls-y5sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:mobile" {...props}></Icon>
