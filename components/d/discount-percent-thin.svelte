<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq5kcq0eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cq5kcq0eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:discount-percent-thin" {...props}></Icon>
