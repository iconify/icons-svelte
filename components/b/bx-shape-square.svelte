<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccomurbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccomurbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-shape-square" {...props}></Icon>
