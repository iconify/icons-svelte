<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5cl7x5rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k5cl7x5rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:data-transfer-diagonal" {...props}></Icon>
