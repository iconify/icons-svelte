<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag-n1-y5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ag-n1-y5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:input-check" {...props}></Icon>
