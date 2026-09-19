<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knln1tbfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="knln1tbfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-rtl" {...props}></Icon>
