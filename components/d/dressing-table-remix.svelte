<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llrxv2dez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="llrxv2dez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:dressing-table-remix" {...props}></Icon>
