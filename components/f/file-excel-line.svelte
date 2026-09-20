<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksvfn86nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksvfn86nr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-excel-line" {...props}></Icon>
