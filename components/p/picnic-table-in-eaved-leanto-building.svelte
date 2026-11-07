<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2702acas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j2702acas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:picnic-table-in-eaved-leanto-building" {...props}></Icon>
