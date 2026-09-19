<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quuc_sk-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="quuc_sk-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:close-circle-o" {...props}></Icon>
