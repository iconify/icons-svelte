<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svb_ag-kk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="svb_ag-kk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:line-height" {...props}></Icon>
