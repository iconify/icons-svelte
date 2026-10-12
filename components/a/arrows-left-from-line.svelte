<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep14q-bov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ep14q-bov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:arrows-left-from-line" {...props}></Icon>
