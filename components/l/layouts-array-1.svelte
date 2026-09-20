<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r01koibir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r01koibir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:layouts-array-1" {...props}></Icon>
