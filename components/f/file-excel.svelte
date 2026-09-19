<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnso9-bfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="nnso9-bfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:file-excel" {...props}></Icon>
