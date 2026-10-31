<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-nz38byv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x-nz38byv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:picnic-table-in-eaved-gabled-building-with-chimney" {...props}></Icon>
