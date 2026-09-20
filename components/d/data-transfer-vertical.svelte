<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3ziveq5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z3ziveq5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:data-transfer-vertical" {...props}></Icon>
