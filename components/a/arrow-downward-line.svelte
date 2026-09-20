<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm_j1ib0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vm_j1ib0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-downward-line" {...props}></Icon>
