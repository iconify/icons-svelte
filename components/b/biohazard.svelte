<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg_wpcd8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":962};
const content = `<path class="kg_wpcd8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:biohazard" {...props}></Icon>
