<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odsr5q1mz.css';
import '../../css/s/sp2z8f1qt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="odsr5q1mz"/><path class="sp2z8f1qt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:filter-bold-duotone" {...props}></Icon>
